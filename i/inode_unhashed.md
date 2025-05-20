# Function: <code>inode_unhashed</code>

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
Location: include/linux/fs.h:682
Inline: True
```
```
In fs/bad_inode.c (0)
Location: include/linux/fs.h:682
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/fs.h:682
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/fs.h:682
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
Location: include/linux/fs.h:704
Inline: True
```
```
In fs/bad_inode.c (0)
Location: include/linux/fs.h:704
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/fs.h:704
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/fs.h:704
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
In mm/shmem.c (0)
Location: include/linux/fs.h:657
Inline: True
```
```
In fs/inode.c (0)
Location: include/linux/fs.h:657
Inline: True
```
```
In fs/bad_inode.c (0)
Location: include/linux/fs.h:657
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/fs.h:657
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/fs.h:657
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
Location: include/linux/fs.h:676
Inline: True
```
```
In fs/bad_inode.c (0)
Location: include/linux/fs.h:676
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/fs.h:676
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/linux/fs.h:676
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/linux/fs.h:676
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
In fs/inode.c (ffffffff8129369d)
Location: include/linux/fs.h:680
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8129551c)
Location: include/linux/fs.h:680
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (0)
Location: include/linux/fs.h:680
Inline: True
```
```
In fs/block_dev.c (ffffffff812b5c09)
Location: include/linux/fs.h:680
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (0)
Location: include/linux/fs.h:680
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
In fs/inode.c (ffffffff812ba3ec)
Location: include/linux/fs.h:682
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812bb725)
Location: include/linux/fs.h:682
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff812ccc1d)
Location: include/linux/fs.h:682
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffffffff812dd4f3)
Location: include/linux/fs.h:682
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (ffffffff8137525b)
Location: include/linux/fs.h:682
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812cf751)
Location: include/linux/fs.h:719
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812d0915)
Location: include/linux/fs.h:719
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff812e1f4d)
Location: include/linux/fs.h:719
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffffffff812f2ad3)
Location: include/linux/fs.h:719
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (ffffffff8138d67b)
Location: include/linux/fs.h:719
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812ec6a3)
Location: include/linux/fs.h:734
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812ed9b5)
Location: include/linux/fs.h:734
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff813009c2)
Location: include/linux/fs.h:734
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffffffff81313d36)
Location: include/linux/fs.h:734
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (ffffffff813b7a6e)
Location: include/linux/fs.h:734
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812fe1f3)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812ff475)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff81313092)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffffffff81327516)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (ffffffff813d9b3e)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff813369a3)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/inode.c:iput_final
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff813384f5)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff8134c9f5)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffffffff81360824)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
```
```
In fs/ext4/super.c (ffffffff8142734e)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
```
```
In block/genhd.c (ffffffff8155a432)
Location: include/linux/fs.h:766
Inline: True
Inline callers:
  - block/genhd.c:invalidate_partition
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
In mm/shmem.c (ffffffff81277950)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - mm/shmem.c:shmem_encode_fh
  - mm/shmem.c:shmem_encode_fh
```
```
In fs/inode.c (ffffffff81342309)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/inode.c:iput_final
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81343e85)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff813599ec)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/ext4/super.c (ffffffff8143e93d)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/fuse/dir.c (ffffffff8148fdaf)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff81499258)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In block/genhd.c (ffffffff81577663)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81579751)
Location: include/linux/fs.h:729
Inline: True
Inline callers:
  - block/partitions/core.c:delete_partition
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
In mm/shmem.c (ffffffff8127cf80)
Location: include/linux/fs.h:730
Inline: True
Inline callers:
  - mm/shmem.c:shmem_encode_fh
  - mm/shmem.c:shmem_encode_fh
```
```
In fs/inode.c (ffffffff81348703)
Location: include/linux/fs.h:730
Inline: True
Inline callers:
  - fs/inode.c:iput_final
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8134a235)
Location: include/linux/fs.h:730
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff813605a2)
Location: include/linux/fs.h:730
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/ext4/super.c (ffffffff8144453d)
Location: include/linux/fs.h:730
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/fuse/dir.c (ffffffff814957e7)
Location: include/linux/fs.h:730
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff8149e3e3)
Location: include/linux/fs.h:730
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff814a0985)
Location: include/linux/fs.h:730
Inline: True
```
```
In block/genhd.c (ffffffff8157f439)
Location: include/linux/fs.h:730
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81580f24)
Location: include/linux/fs.h:730
Inline: True
Inline callers:
  - block/partitions/core.c:delete_partition
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
In mm/shmem.c (ffffffff812bb0d0)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - mm/shmem.c:shmem_encode_fh
  - mm/shmem.c:shmem_encode_fh
```
```
In fs/inode.c (ffffffff81396e6d)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81397f95)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff813aec22)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/ext4/super.c (ffffffff8149833d)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/fuse/dir.c (ffffffff814ed281)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff814f6293)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff814f8855)
Location: include/linux/fs.h:742
Inline: True
```
```
In block/bdev.c (ffffffff815c4c89)
Location: include/linux/fs.h:742
Inline: True
```
```
In block/genhd.c (ffffffff815e35c6)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff815e6819)
Location: include/linux/fs.h:742
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
  - block/partitions/core.c:delete_partition
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
In mm/shmem.c (ffffffff81314d70)
Location: include/linux/fs.h:697
Inline: True
Inline callers:
  - mm/shmem.c:shmem_encode_fh
  - mm/shmem.c:shmem_encode_fh
```
```
In fs/inode.c (ffffffff81418b45)
Location: include/linux/fs.h:697
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8141a535)
Location: include/linux/fs.h:697
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff81433219)
Location: include/linux/fs.h:697
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/ext4/super.c (ffffffff8152300c)
Location: include/linux/fs.h:697
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/fuse/dir.c (ffffffff8157c0fb)
Location: include/linux/fs.h:697
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff815860d3)
Location: include/linux/fs.h:697
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff815885c7)
Location: include/linux/fs.h:697
Inline: True
```
```
In block/bdev.c (ffffffff8166f6bc)
Location: include/linux/fs.h:697
Inline: True
```
```
In block/genhd.c (ffffffff81692856)
Location: include/linux/fs.h:697
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff8169597a)
Location: include/linux/fs.h:697
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
  - block/partitions/core.c:delete_partition
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
In mm/shmem.c (ffffffff81388ca0)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - mm/shmem.c:shmem_encode_fh
  - mm/shmem.c:shmem_encode_fh
```
```
In fs/inode.c (ffffffff814a446b)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff814a63a5)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff814c1582)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/ext4/super.c (ffffffff815c018c)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/fuse/dir.c (ffffffff81621b0b)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff8162c343)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff8162ea87)
Location: include/linux/fs.h:712
Inline: True
```
```
In block/bdev.c (ffffffff8172aa9f)
Location: include/linux/fs.h:712
Inline: True
```
```
In block/genhd.c (ffffffff81750a96)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff81754b8d)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_add_partition
  - block/partitions/core.c:delete_partition
```
```
In block/holder.c (ffffffff8178589e)
Location: include/linux/fs.h:712
Inline: True
Inline callers:
  - block/holder.c:bd_link_disk_holder
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
In mm/shmem.c (ffffffff813baed0)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - mm/shmem.c:shmem_encode_fh
  - mm/shmem.c:shmem_encode_fh
```
```
In fs/inode.c (ffffffff814d95e2)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff814db365)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff814f6912)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/ext4/super.c (ffffffff815f792c)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/fuse/dir.c (ffffffff81659f61)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff81664583)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff81666ce7)
Location: include/linux/fs.h:727
Inline: True
```
```
In block/bdev.c (ffffffff81766cde)
Location: include/linux/fs.h:727
Inline: True
```
```
In block/genhd.c (ffffffff8178ce96)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff81790d88)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:bdev_add_partition
```
```
In block/blk-cgroup.c (ffffffff817a22e7)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_open_bdev
```
```
In block/holder.c (ffffffff817c5d08)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - block/holder.c:bd_link_disk_holder
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
In mm/shmem.c (ffffffff813e56d0)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - mm/shmem.c:shmem_encode_fh
  - mm/shmem.c:shmem_encode_fh
```
```
In fs/inode.c (ffffffff8150bd8d)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8150dac5)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - fs/bad_inode.c:iget_failed
```
```
In fs/fs-writeback.c (ffffffff8152b052)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/ext4/super.c (ffffffff816304dc)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
```
```
In fs/fuse/dir.c (ffffffff81693be0)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff8169e793)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff816a0ff7)
Location: include/linux/fs.h:760
Inline: True
```
```
In block/bdev.c (ffffffff817a89a6)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - block/bdev.c:bdev_open_by_dev
```
```
In block/genhd.c (ffffffff817cf6c6)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - block/genhd.c:disk_release
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff817d48f4)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:bdev_add_partition
```
```
In block/blk-cgroup.c (ffffffff817e5e2a)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_open_bdev
```
```
In block/holder.c (ffffffff8180a9f8)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - block/holder.c:bd_link_disk_holder
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
In fs/inode.c (ffff8000103aeb98)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffff8000103b0900)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffff8000103c8844)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffff8000103e24b4)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (ffff8000104b6388)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (c058e8fc)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (c05901fc)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (c05a51ac)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (c05ba688)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (c0675e3c)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (c0000000004a9f74)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (c0000000004ac2a0)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (c0000000004c9d90)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (c0000000004e8130)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (c0000000005e5c30)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffe000273986)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffe000274c58)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffe000286fb0)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffffffe000298a66)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (ffffffe000330602)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812f67d3)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812f7a55)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff8130b672)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffffffff8131faf6)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (ffffffff813d211e)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812e73f3)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812e8675)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff812fc292)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffffffff81310696)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (ffffffff813c2b9e)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812f45e3)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812f5865)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff81309462)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffffffff8131d5c6)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (ffffffff813cf5ae)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff81305525)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff813069f5)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fs-writeback.c (ffffffff81319db0)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/fs-writeback.c:__mark_inode_dirty
```
```
In fs/block_dev.c (ffffffff8132f2c6)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/ext4/super.c (ffffffff813e4b9e)
Location: include/linux/fs.h:748
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
```
</details>
</li>
</ul>

## Differences
