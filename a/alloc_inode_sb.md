# Function: <code>alloc_inode_sb</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81314c45)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_inode
```
```
In fs/inode.c (ffffffff81417dbe)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
```
```
In fs/proc/inode.c (ffffffff8149be15)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/ext4/super.c (ffffffff81521fa5)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/squashfs/super.c (ffffffff81550035)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_alloc_inode
```
```
In fs/hugetlbfs/inode.c (ffffffff81554070)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
```
In fs/fat/inode.c (ffffffff8155f735)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_alloc_inode
```
```
In fs/ecryptfs/super.c (ffffffff81568965)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/fuse/inode.c (ffffffff81584855)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_alloc_inode
```
```
In ipc/mqueue.c (ffffffff815a01f5)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_alloc_inode
```
```
In block/bdev.c (ffffffff8166e455)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc_inode
```
```
In drivers/dax/super.c (ffffffff819e9205)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_alloc_inode
```
```
In net/socket.c (ffffffff81be62e5)
Location: include/linux/fs.h:2963
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_inode
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
In mm/shmem.c (ffffffff81388b55)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_inode
```
```
In fs/inode.c (ffffffff814a357e)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
```
```
In fs/proc/inode.c (ffffffff815306f5)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/ext4/super.c (ffffffff815be9c5)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/squashfs/super.c (ffffffff815f0bc5)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_alloc_inode
```
```
In fs/hugetlbfs/inode.c (ffffffff815f5910)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
```
In fs/fat/inode.c (ffffffff81601a35)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_alloc_inode
```
```
In fs/ecryptfs/super.c (ffffffff8160c2d5)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/fuse/inode.c (ffffffff8162a985)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_alloc_inode
```
```
In ipc/mqueue.c (ffffffff81649b25)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_alloc_inode
```
```
In block/bdev.c (ffffffff81729645)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc_inode
```
```
In drivers/dax/super.c (ffffffff81b658f5)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_alloc_inode
```
```
In net/socket.c (ffffffff81d925a5)
Location: include/linux/fs.h:3117
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_inode
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
In mm/shmem.c (ffffffff813bad85)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_inode
```
```
In fs/inode.c (ffffffff814d86ee)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
```
```
In fs/proc/inode.c (ffffffff81568875)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/ext4/super.c (ffffffff815f5775)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/squashfs/super.c (ffffffff81628c25)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_alloc_inode
```
```
In fs/hugetlbfs/inode.c (ffffffff8162d980)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
```
In fs/fat/inode.c (ffffffff81639925)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_alloc_inode
```
```
In fs/ecryptfs/super.c (ffffffff816441c5)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/fuse/inode.c (ffffffff81662ba5)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_alloc_inode
```
```
In ipc/mqueue.c (ffffffff81682085)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_alloc_inode
```
```
In block/bdev.c (ffffffff817659b5)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc_inode
```
```
In drivers/dax/super.c (ffffffff81bb8f15)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_alloc_inode
```
```
In net/socket.c (ffffffff81e00965)
Location: include/linux/fs.h:2733
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_inode
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
In mm/shmem.c (ffffffff813e5585)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_inode
```
```
In fs/inode.c (ffffffff8150af7e)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
```
```
In fs/proc/inode.c (ffffffff815a0e95)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_alloc_inode
```
```
In fs/ext4/super.c (ffffffff8162e085)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_inode
```
```
In fs/squashfs/super.c (ffffffff81661e15)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_alloc_inode
```
```
In fs/hugetlbfs/inode.c (ffffffff81666e70)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_alloc_inode
```
```
In fs/fat/inode.c (ffffffff81672e15)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_alloc_inode
```
```
In fs/ecryptfs/super.c (ffffffff8167d755)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - fs/ecryptfs/super.c:ecryptfs_alloc_inode
```
```
In fs/fuse/inode.c (ffffffff8169ceb5)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_alloc_inode
```
```
In ipc/mqueue.c (ffffffff816be485)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - ipc/mqueue.c:mqueue_alloc_inode
```
```
In block/bdev.c (ffffffff817a75b5)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - block/bdev.c:bdev_alloc_inode
```
```
In drivers/dax/super.c (ffffffff81c0d575)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_alloc_inode
```
```
In net/socket.c (ffffffff81ebd065)
Location: include/linux/fs.h:3016
Inline: True
Inline callers:
  - net/socket.c:sock_alloc_inode
```
</details>
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
