# Function: <code>hlist_fake</code>

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
In fs/inode.c (ffffffff81227d7d)
Location: include/linux/list.h:676
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81229a49)
Location: include/linux/list.h:676
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
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
In fs/inode.c (ffffffff812504b6)
Location: include/linux/list.h:676
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81252199)
Location: include/linux/list.h:676
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
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
In fs/inode.c (ffffffff81263556)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812653e9)
Location: include/linux/list.h:692
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
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
In fs/inode.c (ffffffff81270d76)
Location: include/linux/list.h:705
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81272bfb)
Location: include/linux/list.h:705
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff81292e25)
Location: include/linux/list.h:705
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffff812936a9)
Location: include/linux/list.h:706
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8129552b)
Location: include/linux/list.h:706
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff812b5c15)
Location: include/linux/list.h:706
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffff812b96f9)
Location: include/linux/list.h:706
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812bb739)
Location: include/linux/list.h:706
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff812dd879)
Location: include/linux/list.h:706
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffff812ce949)
Location: include/linux/list.h:759
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812d0929)
Location: include/linux/list.h:759
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff812f2e59)
Location: include/linux/list.h:759
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffff812eb858)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812ed9c9)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff813148bc)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffff812fd388)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812ff489)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff8132709c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffff81336198)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81338509)
Location: include/linux/list.h:909
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In block/genhd.c (ffffffff8155a43e)
Location: include/linux/list.h:909
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
In fs/inode.c (ffffffff81341b1e)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81343e99)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff8148fdbb)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff81499264)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In block/genhd.c (ffffffff8157766f)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff8157975d)
Location: include/linux/list.h:936
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
In fs/inode.c (ffffffff81347f0e)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8134a249)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff814957f3)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff8149e3ef)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff814a0991)
Location: include/linux/list.h:936
Inline: True
```
```
In block/genhd.c (ffffffff8157f445)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81580f30)
Location: include/linux/list.h:936
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
In fs/inode.c (ffffffff81395b1e)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81397fa9)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff814ed28d)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff814f629f)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff814f8861)
Location: include/linux/list.h:936
Inline: True
```
```
In block/genhd.c (ffffffff815e44a8)
Location: include/linux/list.h:936
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff815e6240)
Location: include/linux/list.h:936
Inline: True
Inline callers:
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
In fs/inode.c (ffffffff814175ec)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8141a549)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff8157c107)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff815860df)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff815885d3)
Location: include/linux/list.h:982
Inline: True
```
```
In block/genhd.c (ffffffff81692dd8)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81695360)
Location: include/linux/list.h:982
Inline: True
Inline callers:
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
In fs/inode.c (ffffffff814a2d5c)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff814a63b9)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff81621b17)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff8162c34f)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff8162ea93)
Location: include/linux/list.h:982
Inline: True
```
```
In block/genhd.c (ffffffff81751bcb)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81754430)
Location: include/linux/list.h:982
Inline: True
Inline callers:
  - block/partitions/core.c:delete_partition
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
In fs/inode.c (ffffffff814d7eac)
Location: include/linux/list.h:997
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff814db379)
Location: include/linux/list.h:997
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff81659f6d)
Location: include/linux/list.h:997
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff8166458f)
Location: include/linux/list.h:997
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff81666cf3)
Location: include/linux/list.h:997
Inline: True
```
```
In block/genhd.c (ffffffff8178dfa2)
Location: include/linux/list.h:997
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81790e08)
Location: include/linux/list.h:997
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
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
In fs/inode.c (ffffffff8150a68c)
Location: include/linux/list.h:1086
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8150dad9)
Location: include/linux/list.h:1086
Inline: True
Inline callers:
  - fs/bad_inode.c:iget_failed
```
```
In fs/fuse/dir.c (ffffffff81693bec)
Location: include/linux/list.h:1086
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff8169e79f)
Location: include/linux/list.h:1086
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff816a1003)
Location: include/linux/list.h:1086
Inline: True
```
```
In block/genhd.c (ffffffff817d07ff)
Location: include/linux/list.h:1086
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff817d4973)
Location: include/linux/list.h:1086
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
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
In fs/inode.c (ffff8000103add7c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffff8000103b0908)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffff8000103e1e30)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (c058dfc4)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (c059020c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (c05ba11c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (c0000000004a8dd8)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (c0000000004ac2b0)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (c0000000004e7948)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffe000272670)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffe000274c5c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffe000298500)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffff812f5968)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812f7a69)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff8131f67c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffff812e6588)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812e8689)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff8131021c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffff812f3778)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812f5879)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff8131d14c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
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
In fs/inode.c (ffffffff81304ba6)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81306a09)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff8132ee2c)
Location: include/linux/list.h:819
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
```
</details>
</li>
</ul>

## Differences
