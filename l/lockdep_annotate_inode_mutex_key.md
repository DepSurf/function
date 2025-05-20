# Function: <code>lockdep_annotate_inode_mutex_key</code>

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
In fs/inode.c (0)
Location: include/linux/fs.h:2601
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:2601
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
In fs/inode.c (0)
Location: include/linux/fs.h:2751
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:2751
Inline: True
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
In fs/inode.c (0)
Location: include/linux/fs.h:2720
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:2720
Inline: True
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
In fs/inode.c (0)
Location: include/linux/fs.h:2845
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:2845
Inline: True
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
In fs/inode.c (0)
Location: include/linux/fs.h:2907
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:2907
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
In mm/shmem.c (0)
Location: include/linux/fs.h:2933
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:2933
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:2933
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:2933
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3004
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3004
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3004
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:3004
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3010
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3010
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3010
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:3010
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3123
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3123
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3123
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff814504d6)
Location: include/linux/fs.h:3123
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
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
In mm/shmem.c (0)
Location: include/linux/fs.h:2918
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:2918
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:2918
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8146c9e6)
Location: include/linux/fs.h:2918
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3171
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3171
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3171
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81472216)
Location: include/linux/fs.h:3171
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3159
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3159
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3159
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff814c93c3)
Location: include/linux/fs.h:3159
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
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
In mm/shmem.c (0)
Location: include/linux/fs.h:2925
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:2925
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:2925
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81554dd3)
Location: include/linux/fs.h:2925
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3079
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3079
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3079
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff815f7170)
Location: include/linux/fs.h:3079
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
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
In mm/shmem.c (0)
Location: include/linux/fs.h:2693
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:2693
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:2693
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f230)
Location: include/linux/fs.h:2693
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
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
In mm/shmem.c (0)
Location: include/linux/fs.h:2976
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:2976
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:2976
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81668734)
Location: include/linux/fs.h:2976
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
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
In mm/shmem.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/fs.h:3072
Inline: True
```
</details>
</li>
</ul>

## Differences
