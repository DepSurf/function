# Function: <code>seal_check_future_write</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81282005)
Location: include/linux/mm.h:3229
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8147235d)
Location: include/linux/mm.h:3229
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
In mm/shmem.c (ffffffff812bf695)
Location: include/linux/mm.h:3292
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff814c8b5c)
Location: include/linux/mm.h:3292
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
In mm/shmem.c (ffffffff81316475)
Location: include/linux/mm.h:3427
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mmap
```
```
In fs/hugetlbfs/inode.c (ffffffff815541dc)
Location: include/linux/mm.h:3427
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
In mm/shmem.c (ffffffff8138a693)
Location: include/linux/mm.h:3651
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mmap
```
```
In fs/hugetlbfs/inode.c (ffffffff815f5aa9)
Location: include/linux/mm.h:3651
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
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
In mm/shmem.c (ffffffff813bce4a)
Location: include/linux/mm.h:3870
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mmap
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e313)
Location: include/linux/mm.h:3870
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
</details>
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
