# Function: <code>blkdev_zone_mgmt</code>

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
int blkdev_zone_mgmt(struct block_device *bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81578770)
Location: block/blk-zoned.c:202
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff81578770-ffffffff81578914: blkdev_zone_mgmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_zone_mgmt(struct block_device *bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81595270)
Location: block/blk-zoned.c:202
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff81595270-ffffffff8159543b: blkdev_zone_mgmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_zone_mgmt(struct block_device *bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159c020)
Location: block/blk-zoned.c:194
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff8159c020-ffffffff8159c1d2: blkdev_zone_mgmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_zone_mgmt(struct block_device *bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81604650)
Location: block/blk-zoned.c:265
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff81604650-ffffffff8160480f: blkdev_zone_mgmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blkdev_zone_mgmt(struct block_device *bdev, enum req_opf op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:260
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff81e8df03-ffffffff81e8df65: blkdev_zone_mgmt.cold (STB_LOCAL)
ffffffff816b7db0-ffffffff816b7f83: blkdev_zone_mgmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int blkdev_zone_mgmt(struct block_device *bdev, enum req_op op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:256
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff82077290-ffffffff82077302: blkdev_zone_mgmt.cold (STB_LOCAL)
ffffffff817783c0-ffffffff8177857e: blkdev_zone_mgmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int blkdev_zone_mgmt(struct block_device *bdev, enum req_op op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:250
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff820f72c8-ffffffff820f732a: blkdev_zone_mgmt.cold (STB_LOCAL)
ffffffff817b7c70-ffffffff817b7e6c: blkdev_zone_mgmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blkdev_zone_mgmt(struct block_device *bdev, enum req_op op, sector_t sector, sector_t nr_sectors, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:250
Inline: False
Direct callers:
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
  - block/blk-zoned.c:blkdev_zone_mgmt_ioctl
```
**Symbols:**

```
ffffffff821d4c25-ffffffff821d4d84: blkdev_zone_mgmt.cold (STB_LOCAL)
ffffffff817fcba0-ffffffff817fcd7e: blkdev_zone_mgmt (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum req_opf op</code> ➡️ <code>enum req_op op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
