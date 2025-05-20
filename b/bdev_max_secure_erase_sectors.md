# Function: <code>bdev_max_secure_erase_sectors</code>

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
In block/blk-core.c (ffffffff81679757)
Location: include/linux/blkdev.h:1285
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff816823d1)
Location: include/linux/blkdev.h:1285
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
```
```
In block/ioctl.c (ffffffff81690ad7)
Location: include/linux/blkdev.h:1285
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81b74855)
Location: include/linux/blkdev.h:1285
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_secure_erase_capable
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
In block/blk-core.c (ffffffff81735c05)
Location: include/linux/blkdev.h:1233
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff8173fa6d)
Location: include/linux/blkdev.h:1233
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
```
```
In block/ioctl.c (ffffffff8174f6b8)
Location: include/linux/blkdev.h:1233
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81d11795)
Location: include/linux/blkdev.h:1233
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_secure_erase_capable
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
In block/blk-core.c (ffffffff8177222a)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff8177bf9a)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
```
```
In block/ioctl.c (ffffffff8178ba2a)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81d7abf5)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_secure_erase_capable
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
In block/blk-core.c (ffffffff817b4417)
Location: include/linux/blkdev.h:1199
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-lib.c (ffffffff817be38a)
Location: include/linux/blkdev.h:1199
Inline: True
Inline callers:
  - block/blk-lib.c:blkdev_issue_secure_erase
```
```
In block/ioctl.c (ffffffff817ce188)
Location: include/linux/blkdev.h:1199
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/md/dm-table.c (ffffffff81e31d05)
Location: include/linux/blkdev.h:1199
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_not_secure_erase_capable
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
