# Function: <code>truncate_bdev_range</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int truncate_bdev_range(struct block_device *bdev, fmode_t mode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e2c0)
Location: fs/block_dev.c:110
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff8136e2c0-ffffffff8136e372: truncate_bdev_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int truncate_bdev_range(struct block_device *bdev, fmode_t mode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374bd0)
Location: fs/block_dev.c:110
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff81374bd0-ffffffff81374c82: truncate_bdev_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int truncate_bdev_range(struct block_device *bdev, fmode_t mode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4510)
Location: block/bdev.c:101
Inline: False
Direct callers:
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blk_ioctl_discard
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff815c4510-ffffffff815c45f7: truncate_bdev_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int truncate_bdev_range(struct block_device *bdev, fmode_t mode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166eef0)
Location: block/bdev.c:97
Inline: False
Direct callers:
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff8166eef0-ffffffff8166efcc: truncate_bdev_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int truncate_bdev_range(struct block_device *bdev, fmode_t mode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a1e0)
Location: block/bdev.c:96
Inline: False
Direct callers:
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff8172a1e0-ffffffff8172a2bc: truncate_bdev_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int truncate_bdev_range(struct block_device *bdev, blk_mode_t mode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81766530)
Location: block/bdev.c:96
Inline: False
Direct callers:
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff81766530-ffffffff81766608: truncate_bdev_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int truncate_bdev_range(struct block_device *bdev, blk_mode_t mode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a8060)
Location: block/bdev.c:99
Inline: False
Direct callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_fallocate
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff817a8060-ffffffff817a8138: truncate_bdev_range (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>fmode_t mode</code> ➡️ <code>blk_mode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
