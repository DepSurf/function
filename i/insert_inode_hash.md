# Function: <code>insert_inode_hash</code>

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
In fs/fat/inode.c (ffffffff812fd68d)
Location: include/linux/fs.h:2622
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff81324764)
Location: include/linux/fs.h:2767
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff8133122b)
Location: include/linux/fs.h:2767
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff8133a5ee)
Location: include/linux/fs.h:2736
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff81346f99)
Location: include/linux/fs.h:2736
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff8134f2df)
Location: include/linux/fs.h:2862
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff8135ba01)
Location: include/linux/fs.h:2862
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff8137398f)
Location: include/linux/fs.h:2924
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff81380704)
Location: include/linux/fs.h:2924
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff813a221c)
Location: include/linux/fs.h:2950
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff813aed0d)
Location: include/linux/fs.h:2950
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff813bafdc)
Location: include/linux/fs.h:3022
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff813c7eec)
Location: include/linux/fs.h:3022
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff813e588c)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff813f2ace)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff813ff710)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff8140ca96)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff8144d095)
Location: include/linux/fs.h:3141
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff8145a9ed)
Location: include/linux/fs.h:3141
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/block_dev.c (ffffffff8136e801)
Location: include/linux/fs.h:2951
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_add
```
```
In fs/squashfs/super.c (ffffffff81469702)
Location: include/linux/fs.h:2951
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff81476d3d)
Location: include/linux/fs.h:2951
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/block_dev.c (ffffffff81375111)
Location: include/linux/fs.h:3204
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_add
```
```
In fs/squashfs/super.c (ffffffff8146ee02)
Location: include/linux/fs.h:3204
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff8147c7b1)
Location: include/linux/fs.h:3204
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff814c57f1)
Location: include/linux/fs.h:3192
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff814d3ea6)
Location: include/linux/fs.h:3192
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In block/bdev.c (ffffffff815c4ac1)
Location: include/linux/fs.h:3192
Inline: True
Inline callers:
  - block/bdev.c:bdev_add
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
In fs/squashfs/super.c (ffffffff81550728)
Location: include/linux/fs.h:2969
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff815610ec)
Location: include/linux/fs.h:2969
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In block/bdev.c (ffffffff8166f501)
Location: include/linux/fs.h:2969
Inline: True
Inline callers:
  - block/bdev.c:bdev_add
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
In fs/squashfs/super.c (ffffffff815f1340)
Location: include/linux/fs.h:3123
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff81603574)
Location: include/linux/fs.h:3123
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In block/bdev.c (ffffffff8172a8a1)
Location: include/linux/fs.h:3123
Inline: True
Inline callers:
  - block/bdev.c:bdev_add
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
In fs/squashfs/super.c (ffffffff816293c6)
Location: include/linux/fs.h:2739
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff8163b494)
Location: include/linux/fs.h:2739
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In block/bdev.c (ffffffff81766af1)
Location: include/linux/fs.h:2739
Inline: True
Inline callers:
  - block/bdev.c:bdev_add
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
In fs/squashfs/super.c (ffffffff81662615)
Location: include/linux/fs.h:3022
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff816749f3)
Location: include/linux/fs.h:3022
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
```
In block/bdev.c (ffffffff817a872b)
Location: include/linux/fs.h:3022
Inline: True
Inline callers:
  - block/bdev.c:bdev_add
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
In fs/squashfs/super.c (ffff8000104dd72c)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffff8000104ed6f8)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (c069f320)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (c06ab450)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (c0000000006191f8)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (c00000000062c51c)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffe000352232)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffe00035dcaa)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff813f7cf0)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff81405076)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff813e8770)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff813f5af6)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff813f5070)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff814023f6)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
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
In fs/squashfs/super.c (ffffffff8140aca0)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/fat/inode.c (ffffffff814183c6)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_build_inode
```
</details>
</li>
</ul>

## Differences
