# Function: <code>HUGETLBFS_I</code>

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
In fs/hugetlbfs/inode.c (ffffffff812f3f56)
Location: fs/hugetlbfs/inode.c:63
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_i_callback
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
In fs/hugetlbfs/inode.c (ffffffff81327186)
Location: fs/hugetlbfs/inode.c:63
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_i_callback
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
In fs/hugetlbfs/inode.c (ffffffff8133cef6)
Location: fs/hugetlbfs/inode.c:63
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_i_callback
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
In fs/hugetlbfs/inode.c (ffffffff81351f06)
Location: fs/hugetlbfs/inode.c:63
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_i_callback
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
In fs/hugetlbfs/inode.c (ffffffff81376736)
Location: fs/hugetlbfs/inode.c:63
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_i_callback
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
In mm/memfd.c (ffffffff81293c8d)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (ffffffff813a59b1)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_i_callback
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (ffffffff812a894d)
Location: include/linux/hugetlb.h:296
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf0a1)
Location: include/linux/hugetlb.h:296
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_i_callback
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (ffffffff812c50ad)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (ffffffff813e98e1)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (ffffffff812d6a3d)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (ffffffff81403981)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (ffffffff8130badb)
Location: include/linux/hugetlb.h:428
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff814518a1)
Location: include/linux/hugetlb.h:428
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
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
In mm/memfd.c (ffffffff81317ba1)
Location: include/linux/hugetlb.h:429
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/hugetlbfs/inode.c (ffffffff8146ddc1)
Location: include/linux/hugetlb.h:429
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
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
In mm/memfd.c (ffffffff8131dd91)
Location: include/linux/hugetlb.h:446
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/hugetlbfs/inode.c (ffffffff814738c1)
Location: include/linux/hugetlb.h:446
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (ffffffff8136b134)
Location: include/linux/hugetlb.h:463
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca4d1)
Location: include/linux/hugetlb.h:463
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (0)
Location: include/linux/hugetlb.h:487
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81553dc5)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
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
In mm/memfd.c (0)
Location: include/linux/hugetlb.h:487
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff815f5605)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
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
In mm/memfd.c (0)
Location: include/linux/hugetlb.h:529
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8162d685)
Location: include/linux/hugetlb.h:529
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
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
In mm/memfd.c (0)
Location: include/linux/hugetlb.h:552
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/linux/hugetlb.h:552
Inline: True
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
In mm/memfd.c (ffff80001037bbac)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2120)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (c000000000470ccc)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (c00000000061ec3c)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (ffffffe000252366)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (ffffffe000355e58)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (ffffffff812cf01d)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (ffffffff813fbf61)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (ffffffff812bfcad)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec9e1)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (ffffffff812cce2d)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (ffffffff813f92e1)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/memfd.c (ffffffff812ddbcd)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - mm/memfd.c:memfd_file_seals_ptr
```
```
In fs/hugetlbfs/inode.c (ffffffff8140e8bf)
Location: include/linux/hugetlb.h:282
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_destroy_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_free_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
</details>
</li>
</ul>

## Differences
