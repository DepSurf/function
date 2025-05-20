# Function: <code>remove_inode_hash</code>

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
In fs/inode.c (ffffffff81227d78)
Location: include/linux/fs.h:2628
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81229a44)
Location: include/linux/fs.h:2628
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
In fs/inode.c (ffffffff812504b1)
Location: include/linux/fs.h:2773
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81252194)
Location: include/linux/fs.h:2773
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
In fs/inode.c (ffffffff81263551)
Location: include/linux/fs.h:2742
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812653e4)
Location: include/linux/fs.h:2742
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
In fs/inode.c (ffffffff81270d71)
Location: include/linux/fs.h:2868
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81272bf6)
Location: include/linux/fs.h:2868
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff81292e20)
Location: include/linux/fs.h:2868
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
In fs/inode.c (ffffffff8129369d)
Location: include/linux/fs.h:2930
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8129551c)
Location: include/linux/fs.h:2930
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff812b5c09)
Location: include/linux/fs.h:2930
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
In fs/inode.c (ffffffff812b96ed)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812bb725)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff812dd86d)
Location: include/linux/fs.h:2956
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
In fs/inode.c (ffffffff812ce93d)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812d0915)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff812f2e4d)
Location: include/linux/fs.h:3028
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
In fs/inode.c (ffffffff812eb84b)
Location: include/linux/fs.h:3034
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812ed9b5)
Location: include/linux/fs.h:3034
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff813148b0)
Location: include/linux/fs.h:3034
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
In fs/inode.c (ffffffff812fd37b)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812ff475)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff81327090)
Location: include/linux/fs.h:3096
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
In fs/inode.c (ffffffff8133618b)
Location: include/linux/fs.h:3147
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff813384f5)
Location: include/linux/fs.h:3147
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In block/genhd.c (ffffffff8155a432)
Location: include/linux/fs.h:3147
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
In fs/inode.c (ffffffff81341b11)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81343e85)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff8148fdaf)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff81499258)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In block/genhd.c (ffffffff81577663)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81579751)
Location: include/linux/fs.h:2957
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
In fs/inode.c (ffffffff81347f01)
Location: include/linux/fs.h:3210
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8134a235)
Location: include/linux/fs.h:3210
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff814957e7)
Location: include/linux/fs.h:3210
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff8149e3e3)
Location: include/linux/fs.h:3210
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff814a0985)
Location: include/linux/fs.h:3210
Inline: True
```
```
In block/genhd.c (ffffffff8157f439)
Location: include/linux/fs.h:3210
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81580f24)
Location: include/linux/fs.h:3210
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
In fs/inode.c (ffffffff81395b11)
Location: include/linux/fs.h:3198
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff81397f95)
Location: include/linux/fs.h:3198
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff814ed281)
Location: include/linux/fs.h:3198
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff814f6293)
Location: include/linux/fs.h:3198
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff814f8855)
Location: include/linux/fs.h:3198
Inline: True
```
```
In block/genhd.c (ffffffff815e449c)
Location: include/linux/fs.h:3198
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff815e6234)
Location: include/linux/fs.h:3198
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
In fs/inode.c (ffffffff814175d9)
Location: include/linux/fs.h:2975
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8141a535)
Location: include/linux/fs.h:2975
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff8157c0fb)
Location: include/linux/fs.h:2975
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff815860d3)
Location: include/linux/fs.h:2975
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff815885c7)
Location: include/linux/fs.h:2975
Inline: True
```
```
In block/genhd.c (ffffffff81692dcc)
Location: include/linux/fs.h:2975
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81695354)
Location: include/linux/fs.h:2975
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
In fs/inode.c (ffffffff814a2d49)
Location: include/linux/fs.h:3129
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff814a63a5)
Location: include/linux/fs.h:3129
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff81621b0b)
Location: include/linux/fs.h:3129
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff8162c343)
Location: include/linux/fs.h:3129
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff8162ea87)
Location: include/linux/fs.h:3129
Inline: True
```
```
In block/genhd.c (ffffffff81751bbf)
Location: include/linux/fs.h:3129
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81754424)
Location: include/linux/fs.h:3129
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
In fs/inode.c (ffffffff814d7e99)
Location: include/linux/fs.h:2745
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff814db365)
Location: include/linux/fs.h:2745
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/fuse/dir.c (ffffffff81659f61)
Location: include/linux/fs.h:2745
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff81664583)
Location: include/linux/fs.h:2745
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff81666ce7)
Location: include/linux/fs.h:2745
Inline: True
```
```
In block/genhd.c (ffffffff8178df96)
Location: include/linux/fs.h:2745
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff81790dfc)
Location: include/linux/fs.h:2745
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
In fs/inode.c (ffffffff8150a679)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff8150dac5)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/bad_inode.c:iget_failed
```
```
In fs/fuse/dir.c (ffffffff81693be0)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_getattr
```
```
In fs/fuse/inode.c (ffffffff8169e793)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_iget
```
```
In fs/fuse/readdir.c (ffffffff816a0ff7)
Location: include/linux/fs.h:3028
Inline: True
```
```
In block/genhd.c (ffffffff817d07f3)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
```
```
In block/partitions/core.c (ffffffff817d4967)
Location: include/linux/fs.h:3028
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
In fs/inode.c (ffff8000103add74)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffff8000103b0900)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffff8000103e1e28)
Location: include/linux/fs.h:3096
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
In fs/inode.c (c058dfb8)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (c05901fc)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (c05ba110)
Location: include/linux/fs.h:3096
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
In fs/inode.c (c0000000004a8dcc)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (c0000000004ac2a0)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (c0000000004e793c)
Location: include/linux/fs.h:3096
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
In fs/inode.c (ffffffe00027266c)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffe000274c58)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffe0002984fc)
Location: include/linux/fs.h:3096
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
In fs/inode.c (ffffffff812f595b)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812f7a55)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff8131f670)
Location: include/linux/fs.h:3096
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
In fs/inode.c (ffffffff812e657b)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812e8675)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff81310210)
Location: include/linux/fs.h:3096
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
In fs/inode.c (ffffffff812f376b)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff812f5865)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff8131d140)
Location: include/linux/fs.h:3096
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
In fs/inode.c (ffffffff81304b99)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/inode.c:evict
```
```
In fs/bad_inode.c (ffffffff813069f5)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/bad_inode.c:make_bad_inode
```
```
In fs/block_dev.c (ffffffff8132ee20)
Location: include/linux/fs.h:3096
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_unhash_inode
```
</details>
</li>
</ul>

## Differences
