# Function: <code>bdev_nowait</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81735883)
Location: include/linux/blkdev.h:1269
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In io_uring/io_uring.c (ffffffff8179004d)
Location: include/linux/blkdev.h:1269
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_file_get_flags
  - io_uring/io_uring.c:io_file_get_flags
```
```
In drivers/md/md.c (ffffffff81d02208)
Location: include/linux/blkdev.h:1269
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm-table.c (ffffffff81d11715)
Location: include/linux/blkdev.h:1269
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_nowait_capable
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
In block/fops.c (ffffffff817689d2)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/fops.c:blkdev_open
```
```
In block/blk-core.c (ffffffff81771dc3)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In drivers/md/md.c (ffffffff81d6b33b)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm-table.c (ffffffff81d7ab75)
Location: include/linux/blkdev.h:1256
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_nowait_capable
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
In block/fops.c (ffffffff817aa8bc)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - block/fops.c:blkdev_open
```
```
In block/blk-core.c (ffffffff817b4103)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In drivers/md/md.c (ffffffff81e1cd28)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - drivers/md/md.c:hot_add_disk
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm-table.c (ffffffff81e31c85)
Location: include/linux/blkdev.h:1241
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_nowait_capable
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
