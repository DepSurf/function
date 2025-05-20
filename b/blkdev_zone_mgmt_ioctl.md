# Function: <code>blkdev_zone_mgmt_ioctl</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_zone_mgmt_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81578d80)
Location: block/blk-zoned.c:324
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff81578d80-ffffffff81578ed8: blkdev_zone_mgmt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_zone_mgmt_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815957e0)
Location: block/blk-zoned.c:341
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff815957e0-ffffffff8159598d: blkdev_zone_mgmt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_zone_mgmt_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159c580)
Location: block/blk-zoned.c:333
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff8159c580-ffffffff8159c72d: blkdev_zone_mgmt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_zone_mgmt_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81604bf0)
Location: block/blk-zoned.c:402
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff81604bf0-ffffffff81604dd4: blkdev_zone_mgmt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkdev_zone_mgmt_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff816b83e0)
Location: block/blk-zoned.c:395
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff816b83e0-ffffffff816b85aa: blkdev_zone_mgmt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkdev_zone_mgmt_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817788b0)
Location: block/blk-zoned.c:390
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff817788b0-ffffffff81778a7a: blkdev_zone_mgmt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkdev_zone_mgmt_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817b8480)
Location: block/blk-zoned.c:379
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff817b8480-ffffffff817b862d: blkdev_zone_mgmt_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blkdev_zone_mgmt_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:379
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_common_ioctl
```
**Symbols:**

```
ffffffff821d4dcb-ffffffff821d4de8: blkdev_zone_mgmt_ioctl.cold (STB_LOCAL)
ffffffff817fcf60-ffffffff817fd122: blkdev_zone_mgmt_ioctl (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
