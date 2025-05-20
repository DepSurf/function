# Function: <code>frontswap_test</code>

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
In mm/swapfile.c (ffffffff811d5723)
Location: include/linux/frontswap.h:35
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff811f3748)
Location: include/linux/frontswap.h:40
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff81203fd5)
Location: include/linux/frontswap.h:40
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff8120f673)
Location: include/linux/frontswap.h:40
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff8122aed9)
Location: include/linux/frontswap.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff8124c15c)
Location: include/linux/frontswap.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/swapfile.c (ffffffff81260666)
Location: include/linux/frontswap.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
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
In mm/shmem.c (ffffffff812361f4)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffff8127bb65)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffffffff81244434)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffff8128b645)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffffffff8126e03c)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffff812be51c)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffffffff8127c23c)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffff812ca0ee)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffffffff812813fc)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffff812d0bd1)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffffffff812bc9d1)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffff813162ac)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffff8000102d659c)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffff800010326918)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (c04fe6e8)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (c053e0f8)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
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
In mm/shmem.c (c000000000396860)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (c0000000003fd330)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffffffe0001f1da4)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffe000226ab6)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffffffff8123ca84)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffff81283c25)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffffffff8122fa84)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffff81275aae)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffffffff8123a824)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffff81281a35)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
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
In mm/shmem.c (ffffffff81249f1e)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/swapfile.c (ffffffff8129174f)
Location: include/linux/frontswap.h:48
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
```
</details>
</li>
</ul>

## Differences
