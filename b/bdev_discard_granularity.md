# Function: <code>bdev_discard_granularity</code>

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
In fs/ext4/mballoc.c (0)
Location: include/linux/blkdev.h:1279
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/fat/file.c (ffffffff8155eace)
Location: include/linux/blkdev.h:1279
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In block/blk-lib.c (ffffffff81681bca)
Location: include/linux/blkdev.h:1279
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In drivers/block/loop.c (ffffffff819b5d6b)
Location: include/linux/blkdev.h:1279
Inline: True
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
In fs/ext4/mballoc.c (0)
Location: include/linux/blkdev.h:1227
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/fat/file.c (ffffffff81600cce)
Location: include/linux/blkdev.h:1227
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In block/blk-lib.c (ffffffff8173f1fb)
Location: include/linux/blkdev.h:1227
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In drivers/block/loop.c (ffffffff81b2ae9b)
Location: include/linux/blkdev.h:1227
Inline: True
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
In fs/ext4/mballoc.c (0)
Location: include/linux/blkdev.h:1208
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/fat/file.c (ffffffff81638bbe)
Location: include/linux/blkdev.h:1208
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In block/blk-lib.c (ffffffff8177b765)
Location: include/linux/blkdev.h:1208
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In drivers/block/loop.c (ffffffff81b7b18e)
Location: include/linux/blkdev.h:1208
Inline: True
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
In fs/ext4/mballoc.c (0)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/fat/file.c (ffffffff816720ae)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - fs/fat/file.c:fat_generic_ioctl
```
```
In block/blk-lib.c (ffffffff817bdb55)
Location: include/linux/blkdev.h:1193
Inline: True
Inline callers:
  - block/blk-lib.c:__blkdev_issue_discard
  - block/blk-lib.c:__blkdev_issue_discard
```
```
In drivers/block/loop.c (ffffffff81bcef7e)
Location: include/linux/blkdev.h:1193
Inline: True
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
